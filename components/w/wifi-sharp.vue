<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_f7a-bya.css';
import '../../css/f/fyzd6vw5z.css';
import '../../css/r/r16hmzbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e_f7a-bya"/><path clip-rule="evenodd" class="fyzd6vw5z"/><path clip-rule="evenodd" class="r16hmzbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:wifi-sharp" /></template>
