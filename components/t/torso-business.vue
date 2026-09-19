<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glq10si6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="glq10si6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torso-business" /></template>
