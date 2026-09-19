<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_or7r6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kc_or7r6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-lync" /></template>
