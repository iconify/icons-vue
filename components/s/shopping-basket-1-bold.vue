<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj24m_bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj24m_bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shopping-basket-1-bold" /></template>
