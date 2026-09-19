<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay_6d-p7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ay_6d-p7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-off-fill-12" /></template>
