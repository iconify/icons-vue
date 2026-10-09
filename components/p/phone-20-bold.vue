<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5q5yvb6f.css';
import '../../css/r/rhb8wbjre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o5q5yvb6f"/><path class="rhb8wbjre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-20-bold" /></template>
