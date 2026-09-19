<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cju0fnb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cju0fnb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:scaleway-wordmark" /></template>
