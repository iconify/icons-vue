<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z46p-jbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="z46p-jbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plusminus-circle" /></template>
