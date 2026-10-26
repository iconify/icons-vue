<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp6apm1sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mp6apm1sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:maxillofacial" /></template>
