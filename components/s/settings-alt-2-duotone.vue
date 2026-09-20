<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f2vjo2bea.css';
import '../../css/s/su32efb5p.css';
import '../../css/a/af6c2lt3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f2vjo2bea"/><path class="su32efb5p"/><path class="af6c2lt3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:settings-alt-2-duotone" /></template>
