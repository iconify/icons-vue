<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1wtdyb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1wtdyb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-2-filled" /></template>
