<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyfsf1tvs.css';
import '../../css/a/au3_lid1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyfsf1tvs secondary"/><path class="au3_lid1s primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-duo" /></template>
