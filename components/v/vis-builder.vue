<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_snteb-s.css';
import '../../css/b/b05e0yo7m.css';
import '../../css/t/tnas7_1ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<path clip-rule="evenodd" class="b_snteb-s"/><path clip-rule="evenodd" class="b05e0yo7m"/><path clip-rule="evenodd" class="tnas7_1ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-builder" /></template>
