<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2702acas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j2702acas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:picnic-table-in-eaved-leanto-building" /></template>
