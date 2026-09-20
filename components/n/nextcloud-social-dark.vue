<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_fb6mbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_fb6mbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-social-dark" /></template>
