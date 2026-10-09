<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndoo8eizj.css';
import '../../css/n/npq26_zsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ndoo8eizj"/><path class="npq26_zsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltmeter-48" /></template>
