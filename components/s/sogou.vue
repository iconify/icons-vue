<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz9f6kbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9f6kbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sogou" /></template>
