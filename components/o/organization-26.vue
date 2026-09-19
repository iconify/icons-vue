<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og17uacas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="og17uacas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:organization-26" /></template>
