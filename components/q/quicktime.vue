<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpa7bhnqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpa7bhnqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:quicktime" /></template>
