<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5i2jdjzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y5i2jdjzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:salad-20" /></template>
