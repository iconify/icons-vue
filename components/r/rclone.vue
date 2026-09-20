<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtt2647pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtt2647pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rclone" /></template>
