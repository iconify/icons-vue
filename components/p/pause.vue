<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzwv6sbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yzwv6sbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pause" /></template>
