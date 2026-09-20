<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bic91mcwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bic91mcwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:twitter" /></template>
