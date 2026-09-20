<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke56rmbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ke56rmbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shelter-11" /></template>
