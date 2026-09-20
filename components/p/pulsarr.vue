<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl17irjlu.css';
import '../../css/f/fjge1xbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="xl17irjlu"/><path class="fjge1xbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pulsarr" /></template>
