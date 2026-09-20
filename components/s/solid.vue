<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbrkcx08y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbrkcx08y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:solid" /></template>
