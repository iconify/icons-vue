<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_kog_yln.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_kog_yln"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tank-farm-48" /></template>
