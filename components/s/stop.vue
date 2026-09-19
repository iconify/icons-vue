<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grhjbbbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grhjbbbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:stop" /></template>
