<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqkqu1blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="uqkqu1blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:playstation" /></template>
