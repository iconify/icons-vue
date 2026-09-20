<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jki42v96b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jki42v96b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:send" /></template>
