<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-opjvbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-opjvbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:tracking-outline" /></template>
