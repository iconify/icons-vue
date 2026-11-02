<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psp9dbjum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psp9dbjum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:screwdriver-line" /></template>
