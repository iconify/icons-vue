<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3nkh24xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h3nkh24xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-zerply" /></template>
