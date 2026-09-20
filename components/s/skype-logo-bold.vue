<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs0n-ypkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0n-ypkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:skype-logo-bold" /></template>
