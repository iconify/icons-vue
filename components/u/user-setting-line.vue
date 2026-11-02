<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq9hyqbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq9hyqbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-setting-line" /></template>
