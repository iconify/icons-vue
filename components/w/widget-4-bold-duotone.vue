<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5yirlatd.css';
import '../../css/o/ozjn960ga.css';
import '../../css/z/zi-y_bbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5yirlatd"/><path class="ozjn960ga"/><path class="zi-y_bbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-4-bold-duotone" /></template>
