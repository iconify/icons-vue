<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zadz1fz-o.css';
import '../../css/o/oghs20fic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zadz1fz-o"/><path class="oghs20fic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:umbrella-sharp" /></template>
