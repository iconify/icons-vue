<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap6udxlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wap6udxlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:voicemail" /></template>
