<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b351edb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b351edb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:zoom-logo-1-solid" /></template>
