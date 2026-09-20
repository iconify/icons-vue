<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe1f4abji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qe1f4abji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skateboard-deck" /></template>
