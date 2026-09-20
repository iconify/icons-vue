<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ob0rwgj.css';
import '../../css/m/m7levstwq.css';
import '../../css/b/b770eaceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q3ob0rwgj"/><path class="m7levstwq"/><path class="b770eaceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:option" /></template>
