<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxht3kjug.css';
import '../../css/j/jm_1qebhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxht3kjug"/><path class="jm_1qebhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zrok-light" /></template>
