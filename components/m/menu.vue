<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_emwl_aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o_emwl_aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:menu" /></template>
