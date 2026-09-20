<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3hs87bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3hs87bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-3d-variant" /></template>
