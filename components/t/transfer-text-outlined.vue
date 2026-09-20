<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br4wb9f0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br4wb9f0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:transfer-text-outlined" /></template>
