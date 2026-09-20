<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujj4-jdsj.css';
import '../../css/h/hbovmzbev.css';
import '../../css/u/uc21-y-ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujj4-jdsj"/><path class="hbovmzbev"/><path class="uc21-y-ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nx-witness-dark" /></template>
