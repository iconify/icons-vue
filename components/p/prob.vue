<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d185acboo.css';
import '../../css/o/o4dhdybxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d185acboo"/><path class="o4dhdybxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:prob" /></template>
