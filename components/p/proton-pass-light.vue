<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1kxjsbic.css';
import '../../css/e/e0vgkpblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1kxjsbic"/><path class="e0vgkpblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-pass-light" /></template>
