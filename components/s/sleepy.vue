<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h32t530tv.css';
import '../../css/n/n9cednr3v.css';
import '../../css/q/qimkehb6h.css';
import '../../css/n/nbdifrb_t.css';
import '../../css/m/mxfwz8lur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h32t530tv"/><path class="n9cednr3v"/><path class="qimkehb6h"/><path class="nbdifrb_t"/><path class="mxfwz8lur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sleepy" /></template>
