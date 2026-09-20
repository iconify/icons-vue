<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6-m_kb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6-m_kb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:vanity-outline" /></template>
