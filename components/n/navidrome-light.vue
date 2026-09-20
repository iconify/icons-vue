<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtfe-5bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtfe-5bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:navidrome-light" /></template>
