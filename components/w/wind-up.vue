<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v10jh_lld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v10jh_lld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:wind-up" /></template>
