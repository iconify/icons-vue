<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aseipeq2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aseipeq2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidarr" /></template>
