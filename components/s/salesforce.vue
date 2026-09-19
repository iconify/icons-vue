<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9yi8_btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="r9yi8_btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:salesforce" /></template>
