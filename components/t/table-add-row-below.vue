<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9hkrgbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m9hkrgbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:table-add-row-below" /></template>
