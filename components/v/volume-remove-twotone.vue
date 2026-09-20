<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqgjrf.css';
import '../../css/i/iw1iew.css';
import '../../css/i/i794zx.css';
import '../../css/y/y4wbml.css';
import '../../css/y/yvqxys.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-34.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqgjrf iw1iew"/><path class="i794zx iw1iew y4wbml"/><path class="iw1iew y4wbml yvqxys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:volume-remove-twotone" /></template>
