<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ltur30r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4ltur30r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:print-filled" /></template>
