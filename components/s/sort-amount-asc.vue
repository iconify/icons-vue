<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqd5hab-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="lqd5hab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sort-amount-asc" /></template>
