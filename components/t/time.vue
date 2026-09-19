<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhgofuz7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="nhgofuz7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:time" /></template>
