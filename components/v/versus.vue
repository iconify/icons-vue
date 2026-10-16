<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psdvcpval.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psdvcpval"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:versus" /></template>
