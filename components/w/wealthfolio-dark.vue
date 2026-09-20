<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyb-cgbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyb-cgbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wealthfolio-dark" /></template>
