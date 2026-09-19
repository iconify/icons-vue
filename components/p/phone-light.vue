<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxyqm2j5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxyqm2j5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:phone-light" /></template>
