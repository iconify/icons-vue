<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq_6gjbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_6gjbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-swap-outline" /></template>
