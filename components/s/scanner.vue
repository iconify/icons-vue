<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7y63b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="sv7y63b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:scanner" /></template>
