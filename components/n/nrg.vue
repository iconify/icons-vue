<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gctprv6nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gctprv6nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nrg" /></template>
