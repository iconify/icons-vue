<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3m_2pbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3m_2pbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:overcast-logo-block" /></template>
