<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqrktx3bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gqrktx3bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:systemd-wordmark" /></template>
