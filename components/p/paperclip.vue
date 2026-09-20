<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc237m_zh.css';
import '../../css/i/i_kfg6brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oc237m_zh"/><path class="i_kfg6brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:paperclip" /></template>
