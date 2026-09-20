<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnaerzb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnaerzb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:protonmail-logo-2-solid" /></template>
