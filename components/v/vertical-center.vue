<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibnuai-km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibnuai-km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-center" /></template>
