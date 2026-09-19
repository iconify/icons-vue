<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdnwclpgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdnwclpgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:redo" /></template>
