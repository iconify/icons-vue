<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nns0k0bcj.css';
import '../../css/g/g7mt9ybuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="nns0k0bcj"/><path clip-rule="evenodd" class="g7mt9ybuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:search-2" /></template>
