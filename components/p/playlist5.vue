<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcm3uljej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jcm3uljej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:playlist5" /></template>
