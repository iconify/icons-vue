<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0b-rzvep.css';
import '../../css/x/xcvr3hbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0b-rzvep"/><path clip-rule="evenodd" class="xcvr3hbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:phone" /></template>
