<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_6d-1f-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="g_6d-1f-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:people-team" /></template>
