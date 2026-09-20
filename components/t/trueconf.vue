<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pojo69bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pojo69bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trueconf" /></template>
