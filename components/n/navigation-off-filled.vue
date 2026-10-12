<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttn1zkbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttn1zkbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:navigation-off-filled" /></template>
