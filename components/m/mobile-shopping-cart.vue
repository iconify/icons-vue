<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/aagj8rb-s.css';
import '../../css/t/ts9ku-_3j.css';
import '../../css/x/xtd5vdbdb.css';
import '../../css/l/lnoconbjb.css';
import '../../css/e/e213_db7s.css';
import '../../css/c/cbikig4ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="aagj8rb-s"/><path class="ts9ku-_3j"/><path class="xtd5vdbdb"/><path class="lnoconbjb"/><path class="e213_db7s"/><path class="cbikig4ca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:mobile-shopping-cart" /></template>
