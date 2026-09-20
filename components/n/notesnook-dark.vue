<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsna-cb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rsna-cb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notesnook-dark" /></template>
