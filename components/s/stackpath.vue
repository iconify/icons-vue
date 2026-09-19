<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8hx9ob2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o8hx9ob2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stackpath" /></template>
