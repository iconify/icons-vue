<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ada492bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ada492bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:programming-arrows-filled" /></template>
