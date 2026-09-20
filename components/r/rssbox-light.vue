<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhvi1ejec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhvi1ejec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rssbox-light" /></template>
