<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/god5aqbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="god5aqbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-italic" /></template>
