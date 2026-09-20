<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilpcvfb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpcvfb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:touchpad-off" /></template>
