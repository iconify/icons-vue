<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br3d1gslt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":467,"height":512};
const content = `<path class="br3d1gslt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:typedoc" /></template>
