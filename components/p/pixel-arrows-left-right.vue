<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp6ykob9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mp6ykob9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrows-left-right" /></template>
