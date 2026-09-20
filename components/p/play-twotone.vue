<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c14jiy.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-38.css';
import '../../css/f/fill-to-0_3.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c14jiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:play-twotone" /></template>
