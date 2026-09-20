<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcj-5rgqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dcj-5rgqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:medical-bag-remix" /></template>
