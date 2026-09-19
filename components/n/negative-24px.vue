<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp5sjyb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hp5sjyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:negative-24px" /></template>
