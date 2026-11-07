<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj_moacsg.css';
import '../../css/s/s2bjr04lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj_moacsg"/><path clip-rule="evenodd" class="s2bjr04lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-square-bold" /></template>
