<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljidw1u1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljidw1u1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vito-light" /></template>
