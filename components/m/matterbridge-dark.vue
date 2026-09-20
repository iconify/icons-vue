<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9_8tiwpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9_8tiwpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matterbridge-dark" /></template>
