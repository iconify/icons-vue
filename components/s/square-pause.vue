<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waa-u4n5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waa-u4n5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-pause" /></template>
