<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy1unsnmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy1unsnmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-indent-01" /></template>
