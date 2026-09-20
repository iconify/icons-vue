<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f83g-5b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f83g-5b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rome" /></template>
