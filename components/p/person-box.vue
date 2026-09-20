<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_-njn0sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_-njn0sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-box" /></template>
