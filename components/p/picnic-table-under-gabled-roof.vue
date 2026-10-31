<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8cjq9bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n8cjq9bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:picnic-table-under-gabled-roof" /></template>
