<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izn2dcbwr.css';
import '../../css/a/au2mywbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izn2dcbwr"/><path class="au2mywbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:router-signal-bold" /></template>
