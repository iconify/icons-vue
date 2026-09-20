<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiyt5-euh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiyt5-euh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-off" /></template>
