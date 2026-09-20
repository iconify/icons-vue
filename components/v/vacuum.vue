<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqqfp3yew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cqqfp3yew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:vacuum" /></template>
