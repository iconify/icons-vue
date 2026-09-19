<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0-webzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ak0-webzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tab" /></template>
