<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpfjnxb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lpfjnxb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rocking-horse" /></template>
