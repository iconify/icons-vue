<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ike5_5lfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ike5_5lfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:shield" /></template>
