<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2yxnrbti.css';
import '../../css/l/lcxfshbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2yxnrbti"/><path class="lcxfshbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tariff-20" /></template>
