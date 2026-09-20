<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en3f2o17m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="en3f2o17m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rustfs-light" /></template>
