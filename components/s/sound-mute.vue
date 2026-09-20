<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-1joob1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-1joob1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sound-mute" /></template>
