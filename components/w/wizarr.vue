<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn0wiolsr.css';
import '../../css/b/bcj4m3bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="wn0wiolsr"/><path class="bcj4m3bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wizarr" /></template>
