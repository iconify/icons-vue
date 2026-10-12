<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r1ewd6o7u.css';
import '../../css/z/za_8z_t8j.css';
import '../../css/h/h7gz2uwiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r1ewd6o7u"/><path class="za_8z_t8j"/><path class="h7gz2uwiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:step-back-duotone" /></template>
