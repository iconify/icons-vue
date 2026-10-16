<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fumtpyb2y.css';
import '../../css/q/q0nsod9nw.css';
import '../../css/b/bvd_dyb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":630,"height":630,"left":200,"top":200};
const content = `<g paint-order="stroke"><path class="fumtpyb2y"/><path class="q0nsod9nw"/><path class="bvd_dyb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:onedev" /></template>
