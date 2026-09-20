<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drh686bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="drh686bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:x-p-ferd-dark" /></template>
