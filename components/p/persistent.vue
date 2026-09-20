<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi7w48ugf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi7w48ugf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:persistent" /></template>
