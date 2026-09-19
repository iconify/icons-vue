<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xab1o5-0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xab1o5-0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plus-shield-filled" /></template>
