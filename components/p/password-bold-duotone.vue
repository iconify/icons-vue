<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvcm_2wyi.css';
import '../../css/o/oqai2m_dh.css';
import '../../css/u/u7dt5acml.css';
import '../../css/v/v2xxlybwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcm_2wyi"/><path class="oqai2m_dh"/><path class="u7dt5acml"/><path class="v2xxlybwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-bold-duotone" /></template>
