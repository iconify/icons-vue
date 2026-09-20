<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx3fx-byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tx3fx-byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-car" /></template>
