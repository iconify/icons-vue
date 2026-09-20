<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3qn_6bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="o3qn_6bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pound" /></template>
