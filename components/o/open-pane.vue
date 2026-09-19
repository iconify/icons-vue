<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftt5f1qgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ftt5f1qgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:open-pane" /></template>
