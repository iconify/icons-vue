<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5h6yubhn.css';
import '../../css/s/sq8kgxbws.css';
import '../../css/k/kk7sa4ekl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5h6yubhn wm-k"/><path class="sq8kgxbws wm-k"/><path class="kk7sa4ekl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:type" /></template>
