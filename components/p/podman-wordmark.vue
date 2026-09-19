<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0o9-wlos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u0o9-wlos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:podman-wordmark" /></template>
