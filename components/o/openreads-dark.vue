<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk3kyxb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fk3kyxb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openreads-dark" /></template>
