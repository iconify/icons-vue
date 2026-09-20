<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0-p_6bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0-p_6bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror-left" /></template>
