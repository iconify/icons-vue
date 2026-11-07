<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9tzwj7ok.css';
import '../../css/b/bzy5eobti.css';
import '../../css/n/nbozb93jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9tzwj7ok"/><path class="bzy5eobti"/><path clip-rule="evenodd" class="nbozb93jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-underline-cross-outline" /></template>
