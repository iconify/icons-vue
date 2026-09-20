<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkioc6b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kkioc6b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newsku" /></template>
