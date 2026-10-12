<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1m_1pbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1m_1pbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-alert-filled" /></template>
