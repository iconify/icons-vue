<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi0fb9bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yi0fb9bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:users-20" /></template>
