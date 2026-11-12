<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trl7bqbmp.css';
import '../../css/d/d9m02bchl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trl7bqbmp"/><path class="d9m02bchl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spirit-airlines" /></template>
