<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-keie.css';
import '../../css/w/w3lddg.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-76.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-keie"/><path class="w3lddg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:thumbs-up-twotone" /></template>
