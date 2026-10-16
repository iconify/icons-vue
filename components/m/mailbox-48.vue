<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a66xx_uzh.css';
import '../../css/c/c79jlob-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a66xx_uzh"/><path class="c79jlob-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mailbox-48" /></template>
