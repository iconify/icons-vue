<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-nvwe0tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-nvwe0tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music-alt-2" /></template>
