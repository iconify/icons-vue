<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tas58qb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tas58qb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-schedule" /></template>
