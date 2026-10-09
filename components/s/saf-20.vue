<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyzll6bdo.css';
import '../../css/z/z6uphtb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oyzll6bdo"/><path class="z6uphtb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saf-20" /></template>
