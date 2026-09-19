<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idzswcbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idzswcbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tick-double-02" /></template>
