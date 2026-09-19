<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc_jqu9oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="oc_jqu9oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:metronome" /></template>
