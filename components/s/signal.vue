<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-xxmjqjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-xxmjqjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:signal" /></template>
