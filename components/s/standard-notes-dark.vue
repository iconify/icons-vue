<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn5osginn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sn5osginn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:standard-notes-dark" /></template>
