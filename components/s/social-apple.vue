<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9rpk5b8h.css';
import '../../css/y/yt58xlb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9rpk5b8h"/><path class="yt58xlb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-apple" /></template>
