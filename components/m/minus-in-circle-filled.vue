<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sznq_fb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sznq_fb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:minus-in-circle-filled" /></template>
