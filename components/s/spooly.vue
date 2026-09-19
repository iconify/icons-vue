<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orcu3eaid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orcu3eaid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spooly" /></template>
