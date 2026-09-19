<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilegohbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ilegohbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-ss01-small-filled" /></template>
