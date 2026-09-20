<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m45nlgbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m45nlgbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:packing-box-filled" /></template>
