<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvv0o5bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvv0o5bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamlink-light" /></template>
