<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdc-lubcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bdc-lubcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mars" /></template>
