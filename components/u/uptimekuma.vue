<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti3fx-b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti3fx-b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:uptimekuma" /></template>
