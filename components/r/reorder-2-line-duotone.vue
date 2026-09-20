<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pt6j8yqtd.css';
import '../../css/u/ua4c9ibli.css';
import '../../css/t/t418qsbpm.css';
import '../../css/y/yjjibyi4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pt6j8yqtd"/><path class="ua4c9ibli"/><path class="t418qsbpm"/><path class="yjjibyi4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-2-line-duotone" /></template>
