<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfm-5fbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfm-5fbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-protection-1-solid" /></template>
