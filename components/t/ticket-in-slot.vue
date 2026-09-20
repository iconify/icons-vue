<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwk7x1aeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iwk7x1aeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ticket-in-slot" /></template>
