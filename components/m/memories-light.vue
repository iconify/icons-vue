<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok6uxj9nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ok6uxj9nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:memories-light" /></template>
