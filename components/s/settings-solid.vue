<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm6j0-c1z.css';
import '../../css/z/z0f18mbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm6j0-c1z"/><path clip-rule="evenodd" class="z0f18mbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:settings-solid" /></template>
