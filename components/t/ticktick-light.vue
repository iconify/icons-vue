<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjvq-5bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjvq-5bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticktick-light" /></template>
