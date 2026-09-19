<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaiyq5bvp.css';
import '../../css/r/r4lzt7bws.css';
import '../../css/a/apwd9x61f.css';
import '../../css/c/c2x12s28z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="r4lzt7bws"/><path class="apwd9x61f"/><path class="c2x12s28z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ocaml" /></template>
