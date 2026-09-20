<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqmj2n7us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqmj2n7us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pantone-filled" /></template>
