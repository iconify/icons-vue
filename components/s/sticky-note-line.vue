<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hza_l0bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hza_l0bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sticky-note-line" /></template>
