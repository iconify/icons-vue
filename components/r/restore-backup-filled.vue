<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/useuhii4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="useuhii4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:restore-backup-filled" /></template>
