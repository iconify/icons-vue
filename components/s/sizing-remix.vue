<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw6m22bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="aw6m22bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sizing-remix" /></template>
