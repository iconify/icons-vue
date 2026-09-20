<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5_car.css';
import '../../css/n/n5xegl.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5_car"/><path class="n5xegl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-right-half-twotone" /></template>
