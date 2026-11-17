<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by3dv2b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="by3dv2b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tubehaus-dark" /></template>
