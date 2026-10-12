<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sye9drcvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sye9drcvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-phonetic" /></template>
