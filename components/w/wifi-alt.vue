<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoo5lszqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="hoo5lszqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wifi-alt" /></template>
