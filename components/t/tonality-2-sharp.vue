<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai6bcoj1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tonality-2-sharp" /></template>
<style>
.ai6bcoj1c {
  fill: currentColor;
  d: path("M8.1 21.213q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788M11 5v-.95q-.75.125-1.475.338T8.15 5zm0 3V7H5.75q-.2.225-.35.475T5.1 8zm0 3v-1H4.25l-.1.5l-.1.5zm0 3v-1H4.05l.1.5l.1.5zm0 3v-1H5.1q.15.275.3.525t.35.475zm0 2.95V19H8.15q.65.4 1.375.613T11 19.95");
}

</style>
