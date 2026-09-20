<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq9_xubku.css';
import '../../css/x/xdtlmkksx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qq9_xubku"/><path class="ouiIcon__fillSecondary xdtlmkksx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ml-create-advanced-job" /></template>
