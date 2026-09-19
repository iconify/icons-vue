<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wumggdzwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wumggdzwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:personal-hygiene-clean-toothpaste" /></template>
