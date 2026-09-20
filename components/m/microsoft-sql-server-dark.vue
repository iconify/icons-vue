<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz5dvoblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zz5dvoblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sql-server-dark" /></template>
