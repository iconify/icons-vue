<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le9ouvbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le9ouvbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-warning" /></template>
