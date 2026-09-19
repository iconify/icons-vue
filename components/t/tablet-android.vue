<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if33zkffk.css';
import '../../css/f/fa0fk2bvn.css';
import '../../css/g/g7c7tpvnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="if33zkffk"/><path class="fa0fk2bvn"/><path class="g7c7tpvnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:tablet-android" /></template>
