<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xshlwsaiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xshlwsaiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:slate-open-off-outline" /></template>
