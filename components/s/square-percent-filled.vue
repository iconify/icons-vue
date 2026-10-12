<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml22co8ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml22co8ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-percent-filled" /></template>
