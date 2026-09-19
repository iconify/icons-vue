<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fnzuxjcax.css';
import '../../css/u/u4sxwwy9k.css';
import '../../css/b/bum_z6bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fnzuxjcax"/><path class="u4sxwwy9k"/><path class="bum_z6bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rows4" /></template>
