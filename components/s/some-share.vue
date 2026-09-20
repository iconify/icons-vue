<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7s5-gbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7s5-gbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-share" /></template>
