<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx6lgub6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":486,"height":512};
const content = `<path class="lx6lgub6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:neko" /></template>
