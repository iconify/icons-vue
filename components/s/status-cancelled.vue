<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx9__mp1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="xx9__mp1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-cancelled" /></template>
