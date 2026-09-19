<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqvo98owy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqvo98owy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:starbucks" /></template>
