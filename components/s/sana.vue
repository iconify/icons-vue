<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akr4lobep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akr4lobep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sana" /></template>
