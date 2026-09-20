<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3u8vmzwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3u8vmzwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pushbullet" /></template>
