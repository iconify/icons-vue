<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpbx2xb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="fpbx2xb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:video-camera" /></template>
