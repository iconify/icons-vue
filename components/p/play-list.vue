<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4myf3box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="c4myf3box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:play-list" /></template>
