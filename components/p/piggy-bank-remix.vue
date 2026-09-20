<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usn-2bc-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="usn-2bc-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:piggy-bank-remix" /></template>
