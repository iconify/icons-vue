<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moedqhbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moedqhbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:volume" /></template>
