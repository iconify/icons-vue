<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4rw3bb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s4rw3bb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:surf-20-bold" /></template>
