<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmg7h7bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmg7h7bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-setting" /></template>
