<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkji4xtjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkji4xtjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:php" /></template>
