<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8f7hrbpl.css';
import '../../css/u/u9i0xe_nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8f7hrbpl"/><path clip-rule="evenodd" class="u9i0xe_nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pencil-single-light" /></template>
