<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm5dordkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm5dordkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:navigation-x" /></template>
