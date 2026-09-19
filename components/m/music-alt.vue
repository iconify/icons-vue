<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpugvxb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpugvxb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music-alt" /></template>
