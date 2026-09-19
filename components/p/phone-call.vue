<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t758m_bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t758m_bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone-call" /></template>
