<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxmemdtnq.css';
import '../../css/a/az7opmutd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxmemdtnq"/><path class="az7opmutd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:mobile-3" /></template>
