<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkklicbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bkklicbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rescue-ring-stroke-20" /></template>
