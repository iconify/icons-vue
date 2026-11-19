<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vde0oz-fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vde0oz-fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:spiral" /></template>
