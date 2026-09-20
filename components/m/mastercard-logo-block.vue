<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f36i_688s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f36i_688s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastercard-logo-block" /></template>
