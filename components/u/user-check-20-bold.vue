<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw2e5gb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pw2e5gb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-check-20-bold" /></template>
