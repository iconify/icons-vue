<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm_avmgbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm_avmgbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rainbow-solid" /></template>
