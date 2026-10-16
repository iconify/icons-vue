<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na4jw2bku.css';
import '../../css/k/kchk1uyxs.css';
import '../../css/q/qe_9a6udo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="na4jw2bku"/><path class="kchk1uyxs"/><path class="qe_9a6udo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:not-gate-20" /></template>
