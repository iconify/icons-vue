<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if-aux86e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="if-aux86e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:namur-ok" /></template>
