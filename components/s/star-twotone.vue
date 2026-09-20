<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm2tvb.css';
import '../../css/m/mnwdzw.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm2tvb"/><path class="mnwdzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-twotone" /></template>
