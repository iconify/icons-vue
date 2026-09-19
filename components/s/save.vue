<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly7t4lb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":496};
const content = `<path class="ly7t4lb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:save" /></template>
