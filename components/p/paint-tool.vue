<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcymj3gag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcymj3gag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:paint-tool" /></template>
