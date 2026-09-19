<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zo7kwhb-r.css';
import '../../css/v/vm1mqmbgb.css';
import '../../css/e/ehh3wwbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="zo7kwhb-r"/><path class="vm1mqmbgb"/><path class="ehh3wwbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:medical-files" /></template>
