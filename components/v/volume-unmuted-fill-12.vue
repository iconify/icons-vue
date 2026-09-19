<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8lu4nblm.css';
import '../../css/c/c21u_2--p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p8lu4nblm"/><path class="c21u_2--p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-unmuted-fill-12" /></template>
