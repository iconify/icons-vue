<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghge5lbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ghge5lbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:marquee" /></template>
