<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6v-cu3kr.css';
import '../../css/o/o-mw0gu8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a6v-cu3kr"/><path class="o-mw0gu8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:settings-48" /></template>
