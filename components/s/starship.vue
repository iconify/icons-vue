<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9gc9kbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9gc9kbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:starship" /></template>
