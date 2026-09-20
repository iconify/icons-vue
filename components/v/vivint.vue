<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plsztrl7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plsztrl7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vivint" /></template>
