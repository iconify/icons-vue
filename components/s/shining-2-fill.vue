<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgv09jbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgv09jbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shining-2-fill" /></template>
