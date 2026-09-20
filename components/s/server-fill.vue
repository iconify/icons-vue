<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_h3f0hag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_h3f0hag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:server-fill" /></template>
