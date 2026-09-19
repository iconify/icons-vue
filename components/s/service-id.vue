<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho8767n6t.css';
import '../../css/r/rhprpwbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ho8767n6t"/><path class="rhprpwbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:service-id" /></template>
