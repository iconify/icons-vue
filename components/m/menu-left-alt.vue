<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iak9s584k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iak9s584k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-left-alt" /></template>
