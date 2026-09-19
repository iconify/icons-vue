<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agtflua3y.css';
import '../../css/y/yahv79bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agtflua3y"/><path class="yahv79bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:task" /></template>
