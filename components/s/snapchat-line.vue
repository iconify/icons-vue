<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptu9m_w_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptu9m_w_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snapchat-line" /></template>
