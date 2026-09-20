<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqrdo_rwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqrdo_rwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:moon-light" /></template>
