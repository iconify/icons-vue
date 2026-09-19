<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb02adbwv.css';
import '../../css/z/ze1a4qyku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rb02adbwv"/><path class="ze1a4qyku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:position-man" /></template>
