<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv5n3jbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv5n3jbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:minimize-2" /></template>
