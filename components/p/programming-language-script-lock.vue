<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uwalt-_fs.css';
import '../../css/l/l556_r3_t.css';
import '../../css/n/nzs70z7ln.css';
import '../../css/f/fm2ip7bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uwalt-_fs"/><path class="l556_r3_t"/><path class="nzs70z7ln"/><path class="fm2ip7bkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:programming-language-script-lock" /></template>
