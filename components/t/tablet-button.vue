<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-jt6fkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ji-jt6fkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tablet-button" /></template>
