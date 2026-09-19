<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvaupzbfa.css';
import '../../css/p/pfv5fvbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bvaupzbfa"/><path class="pfv5fvbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:reload-outline" /></template>
