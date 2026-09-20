<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":289};
const content = `<path class="soesuq_gb"/><circle transform="matrix(-1 0 0 -1 209.822 367.01)" class="pbrz3mfxd"/><path class="bpe0jebbb"/><path class="tqhzf6bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tauri" /></template>
<style>
.bpe0jebbb {
  fill: var(--svg-color--ffc131, #ffc131);
  d: path("M207.93 192.86a104.8 104.8 0 0 1-36.168 14.717a73.6 73.6 0 0 0 3.617-33.176c29.953-10.472 49.82-38.964 49.292-70.69c-.53-31.727-21.336-59.542-51.622-69.008c-30.286-9.467-63.23 1.546-81.733 27.324a122.2 122.2 0 0 0-40.16 11.723C64.86 29.536 105.956-.445 152.244.005s86.794 31.224 99.636 75.697s-5.026 92.103-43.95 117.157M52.404 92.832l25.693 3.118a73.6 73.6 0 0 1 3.243-14.593a104.8 104.8 0 0 0-28.936 11.475");
}

.pbrz3mfxd {
  cx: 104.911px;
  cy: 183.505px;
  r: 27.439px;
  fill: var(--svg-color--24c8db, #24c8db);
}

.soesuq_gb {
  fill: var(--svg-color--ffc131, #ffc131);
  d: path("M178.497 104.93c0 15.155-12.285 27.44-27.44 27.44c-15.153 0-27.438-12.285-27.438-27.44c0-15.153 12.285-27.438 27.439-27.438s27.439 12.285 27.439 27.439");
}

.tqhzf6bip {
  fill: var(--svg-color--24c8db, #24c8db);
  d: path("M47.913 95.577a104.8 104.8 0 0 1 36.419-14.842a73.46 73.46 0 0 0-4.116 33.3c-29.847 10.619-49.549 39.148-48.906 70.822c.642 31.673 21.484 59.38 51.738 68.78s63.127-1.62 81.604-27.352a122.2 122.2 0 0 0 40.16-11.6c-13.736 44.169-54.812 74.1-101.064 73.645c-46.252-.453-86.733-31.184-99.602-75.612s4.92-92.037 43.768-117.141m155.528 100.026l-.5.25z");
}

</style>
