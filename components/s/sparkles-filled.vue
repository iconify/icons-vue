<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcs4o_c0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcs4o_c0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sparkles-filled" /></template>
