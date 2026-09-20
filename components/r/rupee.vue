<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mka_rwybo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mka_rwybo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rupee" /></template>
