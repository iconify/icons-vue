<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9utlrxw.css';
import '../../css/j/jfmxxebmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb9utlrxw"/><path class="jfmxxebmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-filled" /></template>
