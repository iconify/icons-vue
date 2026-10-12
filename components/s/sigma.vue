<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-xox6byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-xox6byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sigma" /></template>
