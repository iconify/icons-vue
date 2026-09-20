<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv3lzbckl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv3lzbckl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:note-text" /></template>
