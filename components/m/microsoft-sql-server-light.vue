<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oidz_-bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oidz_-bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sql-server-light" /></template>
