<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5eb05w5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5eb05w5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:minus-equal" /></template>
