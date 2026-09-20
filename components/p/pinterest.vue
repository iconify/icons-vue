<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgo7glb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgo7glb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pinterest" /></template>
