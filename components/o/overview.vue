<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gks4ctv1n.css';
import '../../css/m/mk5o0v1xb.css';
import '../../css/s/sua3pvbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="gks4ctv1n"/><path class="mk5o0v1xb"/><path class="sua3pvbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:overview" /></template>
