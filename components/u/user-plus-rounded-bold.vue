<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zh6s_ob7l.css';
import '../../css/i/ice63qb1t.css';
import '../../css/c/c_zdt_bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zh6s_ob7l"/><path class="ice63qb1t"/><path class="c_zdt_bqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-plus-rounded-bold" /></template>
