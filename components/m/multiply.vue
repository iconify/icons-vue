<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/necj-qrta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="necj-qrta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:multiply" /></template>
