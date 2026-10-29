<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvicjx20v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvicjx20v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:redo" /></template>
