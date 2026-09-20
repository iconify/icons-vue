<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpljrfbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpljrfbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:setting-filled" /></template>
