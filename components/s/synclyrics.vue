<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj1lvn23t.css';
import '../../css/e/eionscb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pj1lvn23t"/><path class="eionscb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synclyrics" /></template>
