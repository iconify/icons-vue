<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj5zy-bfd.css';
import '../../css/o/ozjn960ga.css';
import '../../css/z/zi-y_bbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5zy-bfd"/><path class="ozjn960ga"/><path class="zi-y_bbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-4-bold" /></template>
