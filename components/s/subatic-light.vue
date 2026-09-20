<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-ou2rbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-ou2rbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subatic-light" /></template>
