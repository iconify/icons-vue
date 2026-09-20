<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc_jdi2hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc_jdi2hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-day" /></template>
