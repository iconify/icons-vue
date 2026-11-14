<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1lh1ybdm.css';
import '../../css/d/dbja7no2w.css';
import '../../css/f/fntxyg3gk.css';
import '../../css/z/zpp0t1jun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m1lh1ybdm"/><path class="dbja7no2w"/><path class="fntxyg3gk"/><path class="zpp0t1jun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:qodo-wordmark" /></template>
