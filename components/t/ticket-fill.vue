<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njip1cc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="njip1cc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ticket-fill" /></template>
