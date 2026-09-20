<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e28z0dvfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e28z0dvfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-off" /></template>
