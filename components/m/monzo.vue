<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhempj9tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhempj9tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:monzo" /></template>
