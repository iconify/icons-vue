<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df0e-4b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="df0e-4b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:th" /></template>
