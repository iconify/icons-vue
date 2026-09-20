<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aie3zsbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aie3zsbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mask" /></template>
