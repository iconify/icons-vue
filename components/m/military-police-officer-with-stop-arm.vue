<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv7tf3b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qv7tf3b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:military-police-officer-with-stop-arm" /></template>
