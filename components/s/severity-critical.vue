<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8zvaacbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v8zvaacbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:severity-critical" /></template>
