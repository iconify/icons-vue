<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm3-57bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm3-57bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:merge" /></template>
