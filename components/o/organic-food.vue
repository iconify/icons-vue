<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s05wpbmma.css';
import '../../css/c/c02oifziy.css';
import '../../css/v/vi5kufb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s05wpbmma"/><path class="c02oifziy"/><path class="vi5kufb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:organic-food" /></template>
