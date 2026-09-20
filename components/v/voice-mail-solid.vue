<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrevxgb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrevxgb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:voice-mail-solid" /></template>
