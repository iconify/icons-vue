<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5sn8ubxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h5sn8ubxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:windmill-two" /></template>
