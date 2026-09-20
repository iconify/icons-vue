<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8m4hxidg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w8m4hxidg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-end-percent-sharp-fill" /></template>
