<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asa8i895g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asa8i895g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:video-camera" /></template>
