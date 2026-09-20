<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwly73l6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwly73l6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:victronenergy" /></template>
