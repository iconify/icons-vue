<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o112_2buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o112_2buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:receive-pounds" /></template>
