<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz07ytgpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":35};
const content = `<path class="sz07ytgpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:oddinpay" /></template>
