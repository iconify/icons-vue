<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3vz8-xpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3vz8-xpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-square-edit" /></template>
