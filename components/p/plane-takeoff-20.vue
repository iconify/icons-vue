<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui-3y7kiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ui-3y7kiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-takeoff-20" /></template>
