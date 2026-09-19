<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1bi21wia.css';
import '../../css/b/bcpzljbeb.css';
import '../../css/j/jn9mjsb2g.css';
import '../../css/f/fpl1ybcvl.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 m1bi21wia"/><path class="bcpzljbeb clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 jn9mjsb2g"/><path class="clr-i-outline clr-i-outline-path-4 fpl1ybcvl"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:video-gallery-line" /></template>
