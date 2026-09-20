<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyb6zf3uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nyb6zf3uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-inch-floppy-disk" /></template>
