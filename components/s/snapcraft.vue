<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-droyp6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-droyp6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:snapcraft" /></template>
