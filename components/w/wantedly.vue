<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca0t0rb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca0t0rb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wantedly" /></template>
