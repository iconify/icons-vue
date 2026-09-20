<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqvdm-b2t.css';
import '../../css/m/m_u6hpbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqvdm-b2t"/><path class="m_u6hpbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:padlock" /></template>
