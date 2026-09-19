<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqzixhntq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rqzixhntq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:medal" /></template>
