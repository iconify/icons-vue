<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpy2ylyls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpy2ylyls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:utility-pole" /></template>
