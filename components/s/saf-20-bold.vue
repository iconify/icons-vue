<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g39s4_i7q.css';
import '../../css/d/dbz_t_b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g39s4_i7q"/><path class="dbz_t_b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saf-20-bold" /></template>
