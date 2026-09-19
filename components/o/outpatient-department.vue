<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flj_s0bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="flj_s0bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:outpatient-department" /></template>
