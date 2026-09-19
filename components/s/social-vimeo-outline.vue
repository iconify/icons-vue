<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhfv55b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhfv55b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-vimeo-outline" /></template>
