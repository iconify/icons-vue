<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru6sgpi9r.css';
import '../../css/a/aunmnqb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru6sgpi9r"/><path class="aunmnqb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oak-identity-light" /></template>
