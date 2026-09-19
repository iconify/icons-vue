<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef-yoed_f.css';
import '../../css/y/ymnh-3b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ef-yoed_f"/><path class="ymnh-3b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:yugabytedb-wordmark" /></template>
