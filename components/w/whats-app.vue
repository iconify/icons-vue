<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6ea1acit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s6ea1acit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:whats-app" /></template>
