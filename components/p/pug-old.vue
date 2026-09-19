<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv3bzacig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv3bzacig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pug-old" /></template>
