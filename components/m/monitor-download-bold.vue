<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yze9kk29k.css';
import '../../css/v/vojar-box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yze9kk29k"/><path class="vojar-box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monitor-download-bold" /></template>
