<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oexs4c7hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oexs4c7hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-eye" /></template>
