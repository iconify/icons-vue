<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wszt9mr6r.css';
import '../../css/z/zurn3powf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wszt9mr6r"/><path class="zurn3powf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:upload-outline" /></template>
