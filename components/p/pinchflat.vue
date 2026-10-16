<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg5m1db1h.css';
import '../../css/a/a2j6mnb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":608.3,"height":608.3,"left":-17.2,"top":-28.6};
const content = `<path class="fg5m1db1h"/><path class="a2j6mnb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pinchflat" /></template>
