<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqcx_7bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oqcx_7bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:uptime" /></template>
