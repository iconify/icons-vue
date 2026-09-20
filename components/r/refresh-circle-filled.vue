<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs7a4bcmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qs7a4bcmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-circle-filled" /></template>
