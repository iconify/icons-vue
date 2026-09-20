<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lez76uq7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lez76uq7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:powered-pump" /></template>
