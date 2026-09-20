<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scw5hpb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scw5hpb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:x" /></template>
