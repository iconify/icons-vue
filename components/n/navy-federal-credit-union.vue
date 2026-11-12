<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co8fiztgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co8fiztgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:navy-federal-credit-union" /></template>
