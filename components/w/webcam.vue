<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqm_ipb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqm_ipb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:webcam" /></template>
