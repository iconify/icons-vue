<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojitldbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojitldbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:projector-screen-fill" /></template>
