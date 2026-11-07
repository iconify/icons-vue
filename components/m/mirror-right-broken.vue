<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jg7ou40pg.css';
import '../../css/e/eh6mdhb4g.css';
import '../../css/c/cipdabcte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jg7ou40pg"/><path class="eh6mdhb4g"/><path class="cipdabcte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-right-broken" /></template>
