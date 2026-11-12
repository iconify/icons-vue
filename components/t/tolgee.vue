<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn73qtbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pn73qtbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tolgee" /></template>
