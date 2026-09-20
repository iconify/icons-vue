<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnah_ob2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rnah_ob2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:programming-bug" /></template>
