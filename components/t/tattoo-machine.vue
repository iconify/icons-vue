<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvdel6b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gvdel6b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tattoo-machine" /></template>
