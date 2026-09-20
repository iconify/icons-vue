<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grb9lfb6x.css';
import '../../css/n/n3dlx8buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grb9lfb6x"/><path class="n3dlx8buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quire-ink-light" /></template>
