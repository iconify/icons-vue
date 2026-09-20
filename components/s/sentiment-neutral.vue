<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvux82-of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-neutral" /></template>
<style>
.xvux82-of {
  fill: currentColor;
  d: path("M15.312 10.616q.467 0 .789-.327t.322-.793t-.326-.79q-.327-.321-.794-.321t-.789.326t-.322.793t.327.79q.326.322.793.322m-6.615 0q.466 0 .788-.327q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.789.326q-.322.327-.322.793q0 .467.326.79q.327.322.794.322m.457 4.576h5.692v-.884H9.154zm-.661 5.1q-1.643-.709-2.859-1.923t-1.925-2.857T3 12.003t.709-3.51T5.63 5.634t2.857-1.925T11.997 3t3.51.709t2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709q-1.866 0-3.51-.708");
}

</style>
