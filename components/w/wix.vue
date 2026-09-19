<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rktgnbb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rktgnbb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wix" /></template>
