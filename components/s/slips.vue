<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfblkg3qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfblkg3qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:slips" /></template>
