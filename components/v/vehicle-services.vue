<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng6ptzbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ng6ptzbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vehicle-services" /></template>
