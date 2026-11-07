<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nszf3hbuo.css';
import '../../css/m/m_773h0_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nszf3hbuo"/><path class="m_773h0_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:muted-bold-duotone" /></template>
