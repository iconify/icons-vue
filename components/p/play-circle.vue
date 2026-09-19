<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwcmttnff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwcmttnff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:play-circle" /></template>
