<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc0i3r_es.css';
import '../../css/v/vd-a_tg_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc0i3r_es"/><path class="vd-a_tg_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:refresh" /></template>
