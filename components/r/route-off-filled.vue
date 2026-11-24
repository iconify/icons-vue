<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8jmy1b5l.css';
import '../../css/u/ur5d4xvrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8jmy1b5l"/><path class="ur5d4xvrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:route-off-filled" /></template>
