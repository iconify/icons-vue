<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-k-i5ydk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-k-i5ydk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:option-key-48" /></template>
