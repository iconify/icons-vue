<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmo-jlnif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmo-jlnif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:styledcomponents" /></template>
