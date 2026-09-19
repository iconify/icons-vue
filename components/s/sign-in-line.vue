<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo__j3bss.css';
import '../../css/f/f-ef56-ib.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qo__j3bss"/><path class="clr-i-outline clr-i-outline-path-2 f-ef56-ib"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:sign-in-line" /></template>
