<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6fh3-v4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6fh3-v4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-open-sharp-fill" /></template>
