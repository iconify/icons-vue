<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c27ftpu8b.css';
import '../../css/b/blxwk5baf.css';
import '../../css/j/jx7pq2b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c27ftpu8b"/><path class="blxwk5baf"/><path class="jx7pq2b2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sneaker" /></template>
