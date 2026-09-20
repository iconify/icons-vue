<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt8cwocyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pt8cwocyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:quarterstaff" /></template>
