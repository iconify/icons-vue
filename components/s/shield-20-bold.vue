<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4bzr0bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4bzr0bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-20-bold" /></template>
