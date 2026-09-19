<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1t9b8bvt.css';
import '../../css/m/mr-kkz0yl.css';
import '../../css/i/imxhuacrw.css';
import '../../css/n/n839ahj1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1t9b8bvt"/><path class="mr-kkz0yl"/><path class="imxhuacrw"/><g><path class="n839ahj1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-list" /></template>
