<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9jlqc4uo.css';
import '../../css/d/d5_4t-xws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q9jlqc4uo"/><path class="d5_4t-xws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stormkit" /></template>
