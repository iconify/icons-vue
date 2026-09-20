<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_mpelb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_mpelb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:three-squares-outline" /></template>
