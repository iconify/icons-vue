<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqxc8o3zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="oqxc8o3zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:window-restore" /></template>
