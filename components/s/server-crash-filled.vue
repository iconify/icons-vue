<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_kar_p7d.css';
import '../../css/d/dr2vos38o.css';
import '../../css/p/p57dgccqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_kar_p7d"/><path class="dr2vos38o"/><path clip-rule="evenodd" class="p57dgccqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:server-crash-filled" /></template>
