<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5sc99b2m.css';
import '../../css/p/p424nxype.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5sc99b2m"/><path class="p424nxype"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spooty-dark" /></template>
