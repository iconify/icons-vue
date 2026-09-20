<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3m3y7bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3m3y7bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tilda-publishing" /></template>
