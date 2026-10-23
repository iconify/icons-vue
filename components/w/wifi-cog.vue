<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pivpwzbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pivpwzbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wifi-cog" /></template>
