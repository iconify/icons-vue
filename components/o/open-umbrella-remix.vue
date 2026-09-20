<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsnmh2bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zsnmh2bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:open-umbrella-remix" /></template>
