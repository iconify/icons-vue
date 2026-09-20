<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyd9bdc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyd9bdc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rolls-royce" /></template>
