<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbb7tzb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbb7tzb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:snowflake" /></template>
