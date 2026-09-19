<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttk8q5brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttk8q5brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shapes-alt-2-filled" /></template>
