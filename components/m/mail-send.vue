<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/castx7b-i.css';
import '../../css/k/kxk1ljbls.css';
import '../../css/l/lwk02zbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="castx7b-i"/><path class="kxk1ljbls"/><path class="lwk02zbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mail-send" /></template>
