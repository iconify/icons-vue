<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i18ffpbgu.css';
import '../../css/s/s2cfy4b5f.css';
import '../../css/b/bshhd7gtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i18ffpbgu"/><path class="s2cfy4b5f"/><path class="bshhd7gtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pills-duotone" /></template>
