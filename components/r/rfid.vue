<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aij8cd1pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="aij8cd1pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rfid" /></template>
