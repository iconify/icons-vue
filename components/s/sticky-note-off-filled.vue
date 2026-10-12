<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z66sv6m2l.css';
import '../../css/a/am-g_zbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z66sv6m2l"/><path class="am-g_zbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-off-filled" /></template>
