<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xikr_996s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xikr_996s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:plug" /></template>
