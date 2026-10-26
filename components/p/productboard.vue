<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khc6856kd.css';
import '../../css/o/oel1jvbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":42};
const content = `<path class="khc6856kd"/><path class="oel1jvbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:productboard" /></template>
