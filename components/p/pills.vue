<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5f04da_o.css';
import '../../css/z/z6utj2bgt.css';
import '../../css/d/d9xymp2te.css';
import '../../css/y/yl_z4k5yt.css';
import '../../css/s/szhs4bfcc.css';
import '../../css/y/yf6a-mtmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":99.979,"height":99.977};
const content = `<path class="u5f04da_o"/><path class="z6utj2bgt"/><path class="d9xymp2te"/><path class="yl_z4k5yt"/><path class="szhs4bfcc"/><path class="yf6a-mtmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:pills" /></template>
