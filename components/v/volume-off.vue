<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlzdue8eu.css';
import '../../css/u/uibgwrabt.css';
import '../../css/a/a2mdgrbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlzdue8eu wm-k"/><path class="uibgwrabt wm-k"/><path class="a2mdgrbxu wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:volume-off" /></template>
