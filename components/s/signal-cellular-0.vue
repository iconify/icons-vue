<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfxt7ubbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfxt7ubbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:signal-cellular-0" /></template>
