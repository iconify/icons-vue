<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc9osabtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="vc9osabtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:message-alt-writing" /></template>
