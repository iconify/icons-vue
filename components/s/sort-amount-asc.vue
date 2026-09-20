<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eujag_jpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="eujag_jpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sort-amount-asc" /></template>
