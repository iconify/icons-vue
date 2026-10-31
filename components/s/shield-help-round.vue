<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti0u3_bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti0u3_bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-help-round" /></template>
