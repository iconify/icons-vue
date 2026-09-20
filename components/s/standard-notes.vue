<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjmomrbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjmomrbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:standard-notes" /></template>
