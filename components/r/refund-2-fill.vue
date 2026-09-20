<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obtnkwqoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obtnkwqoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:refund-2-fill" /></template>
