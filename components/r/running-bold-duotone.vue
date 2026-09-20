<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/chyhxdobm.css';
import '../../css/l/lm-oqdusd.css';
import '../../css/t/twmpajbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="chyhxdobm"/><path clip-rule="evenodd" class="lm-oqdusd"/><path class="twmpajbfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-bold-duotone" /></template>
