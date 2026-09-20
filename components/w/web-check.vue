<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb6b2hb8b.css';
import '../../css/g/gcoha---j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb6b2hb8b"/><path class="gcoha---j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:web-check" /></template>
