<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahq7b9twm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahq7b9twm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:motogp" /></template>
