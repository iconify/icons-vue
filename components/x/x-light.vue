<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruzq9dyfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ruzq9dyfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:x-light" /></template>
