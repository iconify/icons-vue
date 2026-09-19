<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acxh3fbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="acxh3fbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:phraseapp" /></template>
