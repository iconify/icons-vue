<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lryctbccs.css';
import '../../css/i/iv7ukhb8n.css';
import '../../css/x/xxutnhb6o.css';
import '../../css/x/xwvuugy7n.css';
import '../../css/s/s_aaoy9gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lryctbccs wm-shadow"/><path class="iv7ukhb8n wm-shadow"/><path class="xxutnhb6o"/><path class="xwvuugy7n"/><path class="s_aaoy9gm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:pen-tool" /></template>
