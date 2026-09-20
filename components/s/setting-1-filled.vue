<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5pb81b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5pb81b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:setting-1-filled" /></template>
