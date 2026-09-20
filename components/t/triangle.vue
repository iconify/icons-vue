<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zri1lgb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zri1lgb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:triangle" /></template>
