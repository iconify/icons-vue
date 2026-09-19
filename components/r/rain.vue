<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nza059b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nza059b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rain" /></template>
