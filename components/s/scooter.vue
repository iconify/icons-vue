<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqn5fcb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uqn5fcb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:scooter" /></template>
