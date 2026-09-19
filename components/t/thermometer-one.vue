<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_kwlg0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3_kwlg0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:thermometer-one" /></template>
