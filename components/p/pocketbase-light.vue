<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e462mt2tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e462mt2tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocketbase-light" /></template>
