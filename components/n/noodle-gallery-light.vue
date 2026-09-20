<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5p_-5pyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5p_-5pyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:noodle-gallery-light" /></template>
