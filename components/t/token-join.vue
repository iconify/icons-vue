<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcok2zar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpcok2zar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-join" /></template>
