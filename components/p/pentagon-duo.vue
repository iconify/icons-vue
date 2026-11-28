<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl5rj6b3b.css';
import '../../css/l/las552baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xl5rj6b3b"/><path class="las552baf primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pentagon-duo" /></template>
