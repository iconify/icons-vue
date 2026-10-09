<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtxtpbb-v.css';
import '../../css/w/wrzlzeb2x.css';
import '../../css/j/j3iwccb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wtxtpbb-v"/><path class="wrzlzeb2x"/><path class="j3iwccb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ore-48" /></template>
