<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n69q8ac2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n69q8ac2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wifi-1-filled" /></template>
