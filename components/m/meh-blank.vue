<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qujujdbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="qujujdbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:meh-blank" /></template>
