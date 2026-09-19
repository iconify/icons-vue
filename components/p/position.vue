<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stgrhqeqj.css';
import '../../css/r/rb02adbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="stgrhqeqj"/><path class="rb02adbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:position" /></template>
