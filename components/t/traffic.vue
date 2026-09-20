<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_670hb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h_670hb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:traffic" /></template>
