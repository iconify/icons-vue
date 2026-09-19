<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-cae8ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zw-cae8ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tickets" /></template>
