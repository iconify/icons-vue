<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgvqcohnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qgvqcohnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tlm" /></template>
