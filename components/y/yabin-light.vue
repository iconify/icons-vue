<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi251m7kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi251m7kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yabin-light" /></template>
