<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg5mr5bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg5mr5bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mastercard" /></template>
