<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bl16oqbnl.css';
import '../../css/y/y7y8zfbel.css';
import '../../css/l/l1et1vvup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bl16oqbnl"/><path class="y7y8zfbel"/><path class="l1et1vvup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sledgehammer-line-duotone" /></template>
