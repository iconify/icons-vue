<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv7m_e6md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv7m_e6md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shelving-unit-filled" /></template>
