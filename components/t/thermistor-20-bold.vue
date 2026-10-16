<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8v8c77oa.css';
import '../../css/g/gt6n7jbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m8v8c77oa"/><path class="gt6n7jbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermistor-20-bold" /></template>
