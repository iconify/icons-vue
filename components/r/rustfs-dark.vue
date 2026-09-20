<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtycxbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjtycxbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rustfs-dark" /></template>
