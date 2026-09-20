<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syvbss82p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="syvbss82p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-circle-arrow-down" /></template>
