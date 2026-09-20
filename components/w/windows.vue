<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txtnrsm5l.css';
import '../../css/v/vgxjb1-7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="txtnrsm5l"/><path class="vgxjb1-7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:windows" /></template>
