<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tblh6vbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tblh6vbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:up-solid" /></template>
