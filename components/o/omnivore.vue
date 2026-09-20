<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fje0ntbbb.css';
import '../../css/z/zjmdfw3ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fje0ntbbb"/><path class="zjmdfw3ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnivore" /></template>
