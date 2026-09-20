<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t09269bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t09269bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-holding-open-book" /></template>
