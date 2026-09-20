<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeyo1tnaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="eeyo1tnaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:widget-filled" /></template>
