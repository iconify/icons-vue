<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p1uca-ikg.css';
import '../../css/l/laogv4bch.css';
import '../../css/k/ki04gnhfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p1uca-ikg"/><path class="laogv4bch"/><path class="ki04gnhfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:watch-duotone" /></template>
