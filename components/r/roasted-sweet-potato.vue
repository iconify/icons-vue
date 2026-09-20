<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uc3k1osrr"/><path class="sxnnulbce"/><path class="m0-53hb5f"/><path class="vx7v9vbqx"/><ellipse class="f1kuexb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:roasted-sweet-potato" /></template>
<style>
.f1kuexb5i {
  cx: 11px;
  cy: 29px;
  fill: var(--svg-color--ffd671, #ffd671);
  rx: 10px;
  ry: 4px;
}

.m0-53hb5f {
  fill: var(--svg-color--8e0042, #8e0042);
  d: path("M26.96 6.377c1.14.57 2.703 3.605 2.703 4.506s-.901-.901-2.703-2.704c-1.803-1.802-1.803-2.703 0-1.802m.181 8.03c.607.578 1.009 2.787.836 3.354s-.395-.74-1.183-2.22c-.789-1.48-.615-2.047.347-1.134");
}

.sxnnulbce {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M22.491 14.76c3.816 3.768 4.498 9.263 1.524 12.276s-8.477 2.4-12.294-1.365c-3.816-3.768-4.499-9.264-1.525-12.276c2.975-3.013 8.479-2.401 12.295 1.365");
}

.uc3k1osrr {
  fill: var(--svg-color--b90053, #b90053);
  d: path("M9.441 14.595c.458-1.372 7.41-7.525 13.286-10.22c1.528-.701 6.602-2.834 8.35-3.271C34.681.203 36.167.09 35.666 3.75c-.708 5.171-4.619 12.596-8.707 19.751c-2.68 4.213-4.232 6.423-10.365 3.356c-6.13-3.064-9.196-6.13-7.153-12.262");
}

.vx7v9vbqx {
  fill: var(--svg-color--b90053, #b90053);
  d: path("M21 32c0 2.209-4.477 4-10 4S1 34 1 32c0-.371-.203-2.6.084-2.958C2.34 27.469 6.502 28 11 28c4.908 0 9.133-.865 9.979 1c.107.233.021 2.754.021 3");
}

</style>
