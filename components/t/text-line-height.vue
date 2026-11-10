<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v17wwybmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v17wwybmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-line-height" /></template>
