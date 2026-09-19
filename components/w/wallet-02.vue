<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c2qhvxbop.css';
import '../../css/y/yeh0umb4r.css';
import '../../css/d/dl30k4pxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c2qhvxbop"/><path class="yeh0umb4r"/><path class="dl30k4pxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wallet-02" /></template>
