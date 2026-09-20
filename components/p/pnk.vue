<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly55abcxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly55abcxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pnk" /></template>
