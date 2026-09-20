<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyy18ib3e.css';
import '../../css/h/h5emsl81x.css';
import '../../css/a/ay4nvtb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyy18ib3e"/><path class="h5emsl81x"/><path class="ay4nvtb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sign-in" /></template>
