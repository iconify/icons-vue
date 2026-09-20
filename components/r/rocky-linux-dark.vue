<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu21kfa1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pu21kfa1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rocky-linux-dark" /></template>
