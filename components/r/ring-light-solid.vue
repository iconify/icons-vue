<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-06ykbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-06ykbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ring-light-solid" /></template>
