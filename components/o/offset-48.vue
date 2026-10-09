<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii9mn0isr.css';
import '../../css/w/whuwc1eqk.css';
import '../../css/c/cmlaleo2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ii9mn0isr"/><path class="whuwc1eqk"/><path class="cmlaleo2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offset-48" /></template>
