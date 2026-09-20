<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqad6l3td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iqad6l3td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:outbox" /></template>
