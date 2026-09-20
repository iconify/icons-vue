<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgv6h9b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgv6h9b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:page-included-filled" /></template>
