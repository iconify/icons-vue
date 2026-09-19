<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk2oa9bac.css';
import '../../css/m/m_i62lbim.css';
import '../../css/b/bhnv2njoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="lk2oa9bac"/><circle class="m_i62lbim"/><path class="bhnv2njoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-rounded-dots" /></template>
