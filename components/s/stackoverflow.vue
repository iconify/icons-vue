<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxow2pgrp.css';
import '../../css/t/ta0m-4b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="lxow2pgrp"/><path class="ta0m-4b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:stackoverflow" /></template>
