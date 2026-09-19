<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa0b9abac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fa0b9abac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wireless" /></template>
