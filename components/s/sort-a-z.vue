<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8r-wtbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8r-wtbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sort-a-z" /></template>
