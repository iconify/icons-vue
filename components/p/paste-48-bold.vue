<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adm1b9bzj.css';
import '../../css/s/sizbx91ge.css';
import '../../css/i/iwbhkacly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="adm1b9bzj"/><path class="sizbx91ge"/><path class="iwbhkacly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paste-48-bold" /></template>
