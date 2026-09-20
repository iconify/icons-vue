<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3xin9bnu.css';
import '../../css/m/mqpb9vb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xin9bnu"/><path class="mqpb9vb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-locked-filled" /></template>
