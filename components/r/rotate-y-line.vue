<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9xvu1gdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9xvu1gdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rotate-y-line" /></template>
