<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkapkbbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkapkbbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:merge-solid" /></template>
