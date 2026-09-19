<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jid_jxb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jid_jxb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:mountains" /></template>
