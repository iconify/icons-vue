<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw_cqjble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw_cqjble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-44-small" /></template>
