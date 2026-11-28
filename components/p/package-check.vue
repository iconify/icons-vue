<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ommrk5bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ommrk5bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-check" /></template>
