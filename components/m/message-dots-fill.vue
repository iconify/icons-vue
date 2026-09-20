<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srbggmf_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srbggmf_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-dots-fill" /></template>
