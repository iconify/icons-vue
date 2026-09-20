<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gulrh0bmy.css';
import '../../css/z/z-o2jl6ao.css';
import '../../css/r/rg3jykb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gulrh0bmy"/><path class="z-o2jl6ao"/><path class="rg3jykb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:truenas-core" /></template>
