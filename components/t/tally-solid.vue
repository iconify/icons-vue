<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhfq9qt_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhfq9qt_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-solid" /></template>
