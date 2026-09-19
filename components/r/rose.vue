<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku8r3qb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ku8r3qb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:rose" /></template>
