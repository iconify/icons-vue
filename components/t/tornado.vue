<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogz2-tlnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogz2-tlnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tornado" /></template>
