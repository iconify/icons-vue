<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p49r76-de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p49r76-de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-0-light" /></template>
