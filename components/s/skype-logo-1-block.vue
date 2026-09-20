<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi8krbcyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi8krbcyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:skype-logo-1-block" /></template>
