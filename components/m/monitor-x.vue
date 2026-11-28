<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgzx-tb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzx-tb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-x" /></template>
