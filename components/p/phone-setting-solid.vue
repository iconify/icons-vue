<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmbrdxb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmbrdxb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-setting-solid" /></template>
