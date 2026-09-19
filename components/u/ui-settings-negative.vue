<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l1pqr_bri.css';
import '../../css/x/xu0on341u.css';
import '../../css/p/p88n2yb7u.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsUiSettingsNegative0)" class="cuyn6tgcc"><path class="l1pqr_bri"/><path clip-rule="evenodd" class="xu0on341u"/><path clip-rule="evenodd" class="p88n2yb7u"/></g><defs><clipPath id="healthiconsUiSettingsNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-settings-negative" /></template>
