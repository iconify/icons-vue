<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0y7rc81h.css';
import '../../css/s/s-i43gbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0y7rc81h"/><path class="s-i43gbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:refresh" /></template>
