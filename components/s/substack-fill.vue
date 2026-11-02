<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbaorrbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbaorrbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:substack-fill" /></template>
