<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5uz_v.css';
import '../../css/w/w1kvfb.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-22.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5uz_v"/><path class="w1kvfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:water-twotone" /></template>
