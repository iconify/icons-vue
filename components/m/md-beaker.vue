<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmdssxr9w.css';
import '../../css/d/d709sgber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmdssxr9w"/><path class="d709sgber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-beaker" /></template>
