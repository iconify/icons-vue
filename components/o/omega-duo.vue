<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rig9pzbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rig9pzbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:omega-duo" /></template>
