<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu55lnb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu55lnb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:paperclip" /></template>
