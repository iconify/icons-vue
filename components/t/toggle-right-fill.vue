<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr5ltqbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr5ltqbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-right-fill" /></template>
