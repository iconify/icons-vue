<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9vdhzb3o.css';
import '../../css/h/hdpb60b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9vdhzb3o"/><path class="hdpb60b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-ringing-loud-fill" /></template>
