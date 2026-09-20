<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":260};
const content = `<path class="cvianrm2q"/><path class="qzmtilb_j"/><path class="j-cygl52a"/><path class="chtacgbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pixate" /></template>
<style>
.chtacgbke {
  d: path("M255.254 258.04l-20.888-49.982c-17.904-42.522-34.316-69.378-85.044-69.378h-14.92l14.174 53.712c14.92 57.442 35.808 71.616 106.678 65.648");
  fill: var(--svg-color--0090db, #0090DB);
}

.cvianrm2q {
  d: path("M148.576 67.064l-14.174 53.712h14.92c50.728 0 67.14-26.856 85.044-69.378l20.888-49.982c-70.87-5.222-91.758 8.952-106.678 65.648");
  fill: var(--svg-color--3ec4fc, #3EC4FC);
}

.j-cygl52a {
  d: path("M107.546 193.138l14.174-53.712H106.8c-50.728 0-67.14 26.856-85.044 69.378L.868 258.786c70.87 5.222 91.758-8.952 106.678-65.648");
  fill: var(--svg-color--f18b37, #F18B37);
}

.qzmtilb_j {
  d: path("M.868 2.162l20.888 49.982c17.904 42.522 34.316 69.378 85.044 69.378h14.92L107.546 67.81C92.626 10.368 71.738-3.806.868 2.162");
  fill: var(--svg-color--ffbd00, #FFBD00);
}

</style>
