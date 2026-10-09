<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0heepbom.css';
import '../../css/f/fusgjgx2r.css';
import '../../css/e/egctjry8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d0heepbom"/><path class="fusgjgx2r"/><path class="egctjry8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-alpha-20-bold" /></template>
