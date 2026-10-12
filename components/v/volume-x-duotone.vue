<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z_k8itbaf.css';
import '../../css/h/hbhcawbze.css';
import '../../css/i/i4oj8jbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z_k8itbaf"/><path class="hbhcawbze"/><path class="i4oj8jbzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-x-duotone" /></template>
