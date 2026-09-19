<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0980kf7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="b0980kf7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:treehouse" /></template>
