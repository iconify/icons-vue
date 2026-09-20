<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psxx8-rbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psxx8-rbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-filled" /></template>
