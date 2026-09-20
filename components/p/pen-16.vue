<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec-8y-b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ec-8y-b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pen-16" /></template>
