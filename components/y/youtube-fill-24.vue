<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s10i8bb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s10i8bb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:youtube-fill-24" /></template>
