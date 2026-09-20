<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGPwuarbMS)" class="vb7n012lj"/><path class="q4alhch3i"/><path class="lfqf6mb-m"/><defs><linearGradient id="SVGPwuarbMS" x1="3" x2="21" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="d-a8hjbgl"/><stop offset="1" class="iejxsactl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uncx" /></template>
<style>
.d-a8hjbgl {
  stop-color: var(--svg-color--00c68b, #00c68b);
}

.ft5dv1b6b {
  fill: none;
}

.iejxsactl {
  stop-color: var(--svg-color--00e860, #00e860);
}

.lfqf6mb-m {
  fill: var(--svg-color--c7fcdc, #c7fcdc);
  d: path("M10.312 19.875s-.984-.14-2.812-1.687c1.693.039 4.517.078 5.58-1.654c1.069-1.733-.079-2.785-.45-3.128c0 0 2.317-1.338 2.182-3.094c1.48 1.733 1.688 3.308 1.688 5.063c0 2.11-3.094 4.5-6.188 4.5");
}

.q4alhch3i {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.563 20.438c3.937 0 7.875-4.454 7.875-9c0-.725 0-1.687-.563-2.25c-1.327-1.282-2.599-1.923-2.593-1.918l-.776.867c.01-.023.337-1.041.337-1.064c0 0-1.333-.568-2.537-.64l-.242 1.186l-.157-1.226c-.073 0-1.558-.101-2.83.208l.597 1.08c-.506-.113-.99-.068-1.626.86L8.726 8.3v.005L5.25 7.687l4.067 1.89S7.348 12.67 7.14 13.019c-.22.366-.45 1.018.748 1.322c.225.073.45.118.686.14c1.266-.039 2.425-.472 3.584-.9l.472-.174c.99.872 1.266 2.025.585 3.128c-1.069 1.732-4.022 1.687-5.715 1.654c1.53 1.029 3.094 2.25 5.063 2.25m-.411-10.248l-1.277.94s-.394-.462.113-.845a1.24 1.24 0 0 1 1.164-.095");
}

.vb7n012lj {
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
