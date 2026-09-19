<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiqvv8bip.css';
import '../../css/o/o96_dt2bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="kiqvv8bip"/><path class="o96_dt2bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sun-stroke-16" /></template>
