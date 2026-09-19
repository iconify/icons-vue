<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc-qm3iru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tc-qm3iru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:speaker-deck" /></template>
