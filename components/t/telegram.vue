<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drare1bjj.css';
import '../../css/z/zyog8pxnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drare1bjj"/><path clip-rule="evenodd" class="zyog8pxnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:telegram" /></template>
