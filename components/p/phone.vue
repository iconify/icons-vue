<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekcb249mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekcb249mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:phone" /></template>
