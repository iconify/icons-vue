<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnmkx_dzk.css';
import '../../css/z/z9mmmhbcr.css';
import '../../css/c/ccsgx9gax.css';
import '../../css/r/rvayqzbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="nnmkx_dzk"/><path class="z9mmmhbcr"/><circle class="ccsgx9gax"/><circle class="rvayqzbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mv-4x3" /></template>
