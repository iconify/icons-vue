<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9zy71bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9zy71bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nuke" /></template>
