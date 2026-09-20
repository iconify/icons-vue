<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbt85wbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbt85wbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:odin" /></template>
