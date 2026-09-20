<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drhwmzukw.css';
import '../../css/n/noii36_6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="drhwmzukw"/><path class="noii36_6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pin-slash-16" /></template>
