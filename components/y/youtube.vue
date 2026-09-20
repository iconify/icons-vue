<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g21r9t2-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g21r9t2-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:youtube" /></template>
