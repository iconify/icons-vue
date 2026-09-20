<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr4gfhlan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr4gfhlan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pig-money-fill" /></template>
