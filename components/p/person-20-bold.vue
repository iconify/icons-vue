<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk9dwyb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zk9dwyb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:person-20-bold" /></template>
