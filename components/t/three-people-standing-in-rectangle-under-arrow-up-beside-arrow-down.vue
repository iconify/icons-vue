<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds8oc_btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ds8oc_btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-people-standing-in-rectangle-under-arrow-up-beside-arrow-down" /></template>
