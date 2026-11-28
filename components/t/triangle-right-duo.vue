<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-2db7ux.css';
import '../../css/w/wyrz-1ftw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-2db7ux secondary"/><path class="primary wyrz-1ftw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-right-duo" /></template>
