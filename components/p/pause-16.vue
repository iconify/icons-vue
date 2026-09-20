<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnv5cmbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tnv5cmbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pause-16" /></template>
