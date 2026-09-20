<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1_nn9ipg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1_nn9ipg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:telegram-logo-2-block" /></template>
