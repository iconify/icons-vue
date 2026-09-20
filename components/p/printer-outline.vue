<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01r25bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w01r25bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-outline" /></template>
