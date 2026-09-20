<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny4u_8yny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4u_8yny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tools-kitchen-2-off" /></template>
