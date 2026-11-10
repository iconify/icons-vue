<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_v46-nqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m_v46-nqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-exclamation-20-solid" /></template>
