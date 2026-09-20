<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x70elxbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x70elxbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:nexopia-logo-solid" /></template>
