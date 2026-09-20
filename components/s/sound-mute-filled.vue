<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d00see32g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d00see32g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sound-mute-filled" /></template>
