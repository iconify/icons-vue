<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejvdg2q1j.css';
import '../../css/p/p2_kkklpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ejvdg2q1j"/><path class="p2_kkklpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webhook-48" /></template>
