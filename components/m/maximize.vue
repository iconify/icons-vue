<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv85u99su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv85u99su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:maximize" /></template>
