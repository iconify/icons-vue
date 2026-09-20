<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj0gsaczy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bj0gsaczy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:speed-table" /></template>
