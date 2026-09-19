<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpofilb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpofilb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-thin" /></template>
