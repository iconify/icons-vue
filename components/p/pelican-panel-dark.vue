<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm0jiu4yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dm0jiu4yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pelican-panel-dark" /></template>
