<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6xnjzbga.css';
import '../../css/k/k7by-rbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6xnjzbga"/><path clip-rule="evenodd" class="k7by-rbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pinned-filled" /></template>
