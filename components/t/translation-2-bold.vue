<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv_cx9b4d.css';
import '../../css/q/qi7fugv8z.css';
import '../../css/r/rma8h1e1k.css';
import '../../css/b/b4m79xbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nv_cx9b4d"/><path clip-rule="evenodd" class="qi7fugv8z"/><path class="rma8h1e1k"/><path class="b4m79xbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translation-2-bold" /></template>
