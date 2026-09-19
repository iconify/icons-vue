<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccydevo3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ccydevo3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:slot-machine" /></template>
