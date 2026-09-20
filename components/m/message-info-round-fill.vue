<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c61wmobzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c61wmobzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-info-round-fill" /></template>
