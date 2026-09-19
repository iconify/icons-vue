<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmdffacne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="bmdffacne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:seaalt" /></template>
