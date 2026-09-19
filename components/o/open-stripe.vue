<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agm8mccml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agm8mccml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:open-stripe" /></template>
