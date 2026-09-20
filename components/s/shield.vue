<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i67o6e_jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i67o6e_jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shield" /></template>
