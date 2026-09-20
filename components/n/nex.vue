<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oof_vgboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oof_vgboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nex" /></template>
