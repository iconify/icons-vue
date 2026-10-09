<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb3dfkb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jb3dfkb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-cog-48-bold" /></template>
