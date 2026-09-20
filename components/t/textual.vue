<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5v_jg4cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5v_jg4cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:textual" /></template>
