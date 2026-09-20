<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i6u3v9bup.css';
import '../../css/a/a7jpzibdv.css';
import '../../css/l/l0p7own5h.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i6u3v9bup"/><path class="a7jpzibdv"/><path clip-rule="evenodd" class="l0p7own5h"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:radio-circle" /></template>
