<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dth8-2n2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dth8-2n2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:not-subset-proper-of" /></template>
