<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrui74b0l.css';
import '../../css/k/k-gr6jbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vrui74b0l"/><path class="k-gr6jbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:toggle-on" /></template>
