<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-twxbb6x.css';
import '../../css/z/zt62pibkv.css';
import '../../css/f/fb6cqib6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-twxbb6x"/><rect class="zt62pibkv"/><path class="fb6cqib6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trash-bin-outline" /></template>
