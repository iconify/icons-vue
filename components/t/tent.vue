<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/gmwlybbaz.css';
import '../../css/w/wylacdb1e.css';
import '../../css/d/da3gmy8zl.css';
import '../../css/t/ta0ef9khb.css';
import '../../css/l/lht6sjihy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="gmwlybbaz wm-shadow"/><path class="wm-shadow wylacdb1e"/><path class="da3gmy8zl"/><path class="ta0ef9khb"/><path class="lht6sjihy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:tent" /></template>
