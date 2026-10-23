<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc2xcivwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc2xcivwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:printer" /></template>
