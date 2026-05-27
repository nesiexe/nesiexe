<div align="center">

```aura width=860 height=200 link="https://github.com/nesiexe"
<div style={{
  width: '100%', height: '100%', display: 'flex', flexDirection: 'row', alignItems: 'center',
  fontFamily: 'Inter', borderRadius: 18, overflow: 'hidden',
  background: 'linear-gradient(135deg, #0d1f18 0%, #0d1220 50%, #130d1f 100%)',
  border: '1px solid rgba(140,210,180,0.2)',
}}>
  <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', paddingLeft: 36, flexShrink: 0 }}>
    <div style={{
      display: 'flex', width: 90, height: 90, borderRadius: 45, padding: 2,
      background: 'linear-gradient(135deg, #7de8b0, #7ab8f5, #c4a8f5)',
    }}>
      <div style={{ display: 'flex', width: '100%', height: '100%', borderRadius: 43, overflow: 'hidden', background: '#0d1117' }}>
        <img src={github?.user?.avatarUrl ?? 'https://github.com/nesiexe.png'} width={86} height={86} style={{ borderRadius: 43 }} />
      </div>
    </div>
  </div>
  <div style={{
    display: 'flex', width: 1, height: 100, flexShrink: 0, margin: '0 28px',
    background: 'linear-gradient(to bottom, rgba(140,210,180,0), rgba(140,210,180,0.25), rgba(120,170,255,0.25), rgba(140,210,180,0))',
  }} />
  <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', flex: 1, gap: 6 }}>
    <div style={{ display: 'flex', fontSize: 11, fontWeight: 600, letterSpacing: 2, color: 'rgba(140,210,180,0.65)', textTransform: 'uppercase' }}>
      developer
    </div>
    <div style={{ display: 'flex', fontSize: 34, fontWeight: 800, color: '#e8f0eb', letterSpacing: '-0.5px', lineHeight: 1.05 }}>
      {github?.user?.name || github?.user?.login || 'nesiexe'}
    </div>
    <div style={{ display: 'flex', fontSize: 13, color: 'rgba(160,190,210,0.75)', fontWeight: 400 }}>
      {github?.user?.bio || 'Put here your bio'}
    </div>
    <div style={{ display: 'flex', flexDirection: 'row', gap: 6, marginTop: 6 }}>
      <div style={{ display: 'flex', alignItems: 'center', padding: '4px 13px', borderRadius: 20, fontSize: 12, fontWeight: 600, background: 'rgba(100,210,150,0.12)', border: '1px solid rgba(100,210,150,0.3)', color: '#8de8b8' }}>JavaScript</div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '4px 13px', borderRadius: 20, fontSize: 12, fontWeight: 600, background: 'rgba(100,210,150,0.12)', border: '1px solid rgba(100,210,150,0.3)', color: '#e8ab8d' }}>TypeScript</div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '4px 13px', borderRadius: 20, fontSize: 12, fontWeight: 600, background: 'rgba(120,170,255,0.12)', border: '1px solid rgba(120,170,255,0.3)', color: '#a0c4ff' }}>C#</div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '4px 13px', borderRadius: 20, fontSize: 12, fontWeight: 600, background: 'rgba(100,200,210,0.12)', border: '1px solid rgba(100,200,210,0.3)', color: '#8dd8e8' }}>SQL</div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '4px 13px', borderRadius: 20, fontSize: 12, fontWeight: 600, background: 'rgba(255,223,155,0.12)', border: '1px solid rgba(255,223,155,0.3)', color: '#ffe4aa' }}>CSS</div>
    </div>
  </div>
</div>
```

```aura width=150 height=44 link="https://card.nesiexe.xyz" inline align=center
<SocialMediaButton
  icon="https://nesiexe.xyz/card/assets/nesi.png"
  text="My Card!"
  backgroundColor="#111111"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#b0ffd8' },
    { offset: '60%', color: '#c7b3f7' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
  iconSize="30"
/>
```

```aura width=150 height=44 link="https://t.me/nesiexe" inline align=center
<SocialMediaButton
  icon="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg"
  text="Telegram"
  backgroundColor="#111111"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#29b6f6' },
    { offset: '60%', color: '#81d4fa' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
  iconSize="30"
/>
```

```aura width=150 height=44 link="https://x.com/nesiexe" inline align=center
<SocialMediaButton
  icon="https://upload.wikimedia.org/wikipedia/commons/5/53/X_logo_2023_original.svg"
  text="X"
  backgroundColor="#111111"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#e0e0e0' },
    { offset: '60%', color: '#9e9e9e' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
  iconSize="28"
/>
```

</div>
