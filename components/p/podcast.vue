<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6l-9rbeg.css';
import '../../css/h/hfczz8xtc.css';
import '../../css/z/z8ajtfwob.css';
import '../../css/v/vmomwybeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6l-9rbeg wm-a"/><path class="hfczz8xtc wm-a"/><path class="wm-k z8ajtfwob"/><path class="vmomwybeh wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:podcast" /></template>
