<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crqaz6bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="crqaz6bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:swan" /></template>
