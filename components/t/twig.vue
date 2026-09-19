<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn6a84b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":409,"height":512};
const content = `<path class="sn6a84b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:twig" /></template>
