<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5r0v41yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5r0v41yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-off" /></template>
