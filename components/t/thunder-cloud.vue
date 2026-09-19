<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elc_yybbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="elc_yybbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:thunder-cloud" /></template>
