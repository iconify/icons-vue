<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xhdgozbzy"/><path class="mzqhyqjna"/><path class="ibw5xvbez"/><path class="ofcbpfbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:umbrella" /></template>
<style>
.ibw5xvbez {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M19.5 4C26.403 4 32 9.82 32 17c0 0 0 2-2 2s-5-2-5-2H14s-3 2-5 2s-2-2-2-2C7 9.82 12.596 4 19.5 4");
}

.mzqhyqjna {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M19.5 4C28.612 4 36 9.82 36 17c0 0 0 2-1 2s-3-2-3-2H7s-2 2-3 2s-1-2-1-2C3 9.82 10.387 4 19.5 4");
}

.ofcbpfbgq {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M19.5 4C23.09 4 25 9.82 25 17c0 0-3 2-5 2h-1c-2 0-5-2-5-2c0-7.18 1.91-13 5.5-13");
}

.xhdgozbzy {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M9 28.5a1.5 1.5 0 0 1 3 0v.5s0 3 3 3s3-3 3-3V3.5a1.5 1.5 0 1 1 3 0V29s0 6-6 6s-6-6-6-6z");
}

</style>
