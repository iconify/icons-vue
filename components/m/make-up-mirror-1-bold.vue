<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-bzdbb5h.css';
import '../../css/i/ij-ynac5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-bzdbb5h"/><path class="ij-ynac5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:make-up-mirror-1-bold" /></template>
