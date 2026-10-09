<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvedukegi.css';
import '../../css/d/db1dkebgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vvedukegi"/><path class="db1dkebgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-20-bold" /></template>
