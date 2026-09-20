<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur41y1but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur41y1but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tubes" /></template>
