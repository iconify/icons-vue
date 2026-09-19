<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw9k31bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":700};
const content = `<path class="lw9k31bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:triangle-up" /></template>
