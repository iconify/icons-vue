<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmc-p6bhg.css';
import '../../css/t/tjqy8lb7t.css';
import '../../css/d/dfdn618zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmc-p6bhg"/><path class="tjqy8lb7t"/><path class="dfdn618zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:rose" /></template>
