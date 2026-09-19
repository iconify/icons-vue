<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy8t_d1rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="jy8t_d1rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:organisation" /></template>
