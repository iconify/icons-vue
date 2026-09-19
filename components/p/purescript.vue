<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_pjqt0-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_pjqt0-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:purescript" /></template>
