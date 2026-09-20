<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py1534b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py1534b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-2-outline" /></template>
