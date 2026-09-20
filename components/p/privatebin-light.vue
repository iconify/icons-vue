<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxwc_6_yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxwc_6_yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privatebin-light" /></template>
