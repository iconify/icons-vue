<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z390905ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z390905ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:roadmap-filled" /></template>
