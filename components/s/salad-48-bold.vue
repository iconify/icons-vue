<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tudb-7bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tudb-7bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:salad-48-bold" /></template>
