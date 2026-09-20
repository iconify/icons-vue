<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znun6c7ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znun6c7ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-open" /></template>
