<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeplgj_ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeplgj_ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shape-off" /></template>
