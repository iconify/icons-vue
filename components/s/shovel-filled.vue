<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff3gqsu_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff3gqsu_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shovel-filled" /></template>
