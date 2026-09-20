<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aao1s0bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aao1s0bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seafile-light" /></template>
