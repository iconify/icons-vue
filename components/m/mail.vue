<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwlqrq5ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwlqrq5ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mail" /></template>
