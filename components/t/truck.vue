<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1fvhep4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l1fvhep4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:truck" /></template>
