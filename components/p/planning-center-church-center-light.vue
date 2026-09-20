<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg1ooc8-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eg1ooc8-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-church-center-light" /></template>
