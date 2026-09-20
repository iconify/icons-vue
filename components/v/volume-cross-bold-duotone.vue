<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dagas5qlh.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/d/d7t6d7u5j.css';
import '../../css/b/bfe5y7nus.css';
import '../../css/s/suoqkgb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dagas5qlh"/><g class="mc2zb0bvp"><path class="d7t6d7u5j"/><path class="bfe5y7nus"/><path class="suoqkgb5k"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-cross-bold-duotone" /></template>
