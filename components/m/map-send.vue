<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_-c96hat.css';
import '../../css/d/d-y09zibp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="c_-c96hat"/><path class="d-y09zibp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-send" /></template>
