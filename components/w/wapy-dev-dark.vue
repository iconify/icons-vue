<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l19hjacna.css';
import '../../css/s/snyxhzqyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l19hjacna"/><path class="snyxhzqyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wapy-dev-dark" /></template>
