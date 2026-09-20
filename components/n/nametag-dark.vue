<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym51ckbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ym51ckbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nametag-dark" /></template>
