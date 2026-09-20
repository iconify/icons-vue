<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m11cagbqy.css';
import '../../css/t/tjmji5h6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m11cagbqy"/><path class="tjmji5h6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swagger" /></template>
