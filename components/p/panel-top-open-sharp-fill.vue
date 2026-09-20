<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujfmx-bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujfmx-bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-open-sharp-fill" /></template>
