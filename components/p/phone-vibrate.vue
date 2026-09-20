<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhe0-lb_r.css';
import '../../css/j/jw9xiyagq.css';
import '../../css/x/x2w0zw0xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dhe0-lb_r"/><path class="jw9xiyagq"/><path class="x2w0zw0xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:phone-vibrate" /></template>
