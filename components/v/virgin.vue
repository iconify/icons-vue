<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h34zihb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h34zihb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:virgin" /></template>
