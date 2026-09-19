<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyhlb4b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="hyhlb4b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:water-temperature-70" /></template>
