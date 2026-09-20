<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0-4vtf0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g0-4vtf0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:signin-outline" /></template>
