<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrk88uxja.css';
import '../../css/k/kn5yufbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="kn5yufbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-bottom-48-bold" /></template>
