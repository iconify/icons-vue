<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npzehtboi.css';
import '../../css/o/o887d5btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="npzehtboi"/><path class="o887d5btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:suitcase-rolling-solid" /></template>
