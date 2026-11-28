<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0pakkbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0pakkbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:scale" /></template>
