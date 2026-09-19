<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kufn89bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kufn89bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-circle-question" /></template>
