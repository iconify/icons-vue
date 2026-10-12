<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ste-m-but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ste-m-but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:zzz" /></template>
