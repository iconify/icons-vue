<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srlmpebxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srlmpebxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-long-02-up" /></template>
