<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is7w60blm.css';
import '../../css/a/axtvywb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="is7w60blm"/><path class="axtvywb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-check-20-bold" /></template>
