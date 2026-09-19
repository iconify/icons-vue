<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx-tse73g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":727};
const content = `<path class="hx-tse73g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:skype" /></template>
