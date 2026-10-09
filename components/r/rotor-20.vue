<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zipe_1bgb.css';
import '../../css/w/w2ey4wbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zipe_1bgb"/><path class="w2ey4wbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotor-20" /></template>
