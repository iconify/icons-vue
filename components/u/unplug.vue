<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hun431buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hun431buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:unplug" /></template>
