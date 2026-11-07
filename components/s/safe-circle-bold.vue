<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el80ilbsd.css';
import '../../css/s/s__natbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el80ilbsd"/><path clip-rule="evenodd" class="s__natbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-bold" /></template>
