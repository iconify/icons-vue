<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y85zfp33x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y85zfp33x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wordpress" /></template>
