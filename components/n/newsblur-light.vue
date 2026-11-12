<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hghk2kapn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hghk2kapn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newsblur-light" /></template>
