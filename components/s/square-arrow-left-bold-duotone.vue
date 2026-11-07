<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1bfxqbht.css';
import '../../css/e/e7qclfbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1bfxqbht"/><path class="e7qclfbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-left-bold-duotone" /></template>
