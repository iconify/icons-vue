<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln16226oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ln16226oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-notification" /></template>
