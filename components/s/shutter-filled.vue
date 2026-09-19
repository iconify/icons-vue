<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jipve6o3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jipve6o3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shutter-filled" /></template>
