<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8q00obad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8q00obad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-skip-back-circle-sharp" /></template>
