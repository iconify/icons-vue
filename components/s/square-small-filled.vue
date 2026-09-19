<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgy0d7bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="wgy0d7bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:square-small-filled" /></template>
