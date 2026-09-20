<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu1d-wbfm.css';
import '../../css/h/h7kcmrbin.css';
import '../../css/b/b4959o48o.css';
import '../../css/f/fwcikmbrd.css';
import '../../css/i/iex0o1mku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1512,"height":1511};
const content = `<path class="hu1d-wbfm"/><path class="h7kcmrbin"/><path class="b4959o48o"/><path class="fwcikmbrd"/><path class="iex0o1mku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:masan-group" /></template>
