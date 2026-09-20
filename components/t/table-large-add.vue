<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/majb9u9sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="majb9u9sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-large-add" /></template>
