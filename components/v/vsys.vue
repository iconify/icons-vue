<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpoqxabql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpoqxabql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vsys" /></template>
