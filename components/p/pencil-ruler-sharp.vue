<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cofugbb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cofugbb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pencil-ruler-sharp" /></template>
