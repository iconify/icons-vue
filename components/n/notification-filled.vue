<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9r2hdbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9r2hdbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:notification-filled" /></template>
