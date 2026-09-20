<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_ven-7ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_ven-7ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mediafire" /></template>
