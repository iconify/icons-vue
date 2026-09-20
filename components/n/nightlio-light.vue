<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_aozobks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_aozobks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nightlio-light" /></template>
