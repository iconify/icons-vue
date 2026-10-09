<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d44p8wv5z.css';
import '../../css/t/tb4t4kb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d44p8wv5z"/><path class="tb4t4kb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ore-20" /></template>
