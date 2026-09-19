<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3cygzbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="o3cygzbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:swift" /></template>
