<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta49hdc7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ta49hdc7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:paycheck" /></template>
