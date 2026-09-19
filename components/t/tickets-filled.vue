<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi4k0l1-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi4k0l1-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tickets-filled" /></template>
