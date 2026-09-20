<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkpplc3oo.css';
import '../../css/m/mbgl0xb_o.css';
import '../../css/e/eg0azubuo.css';
import '../../css/k/kz_b-it7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pkpplc3oo"/><path class="mbgl0xb_o"/><path class="eg0azubuo"/><path class="kz_b-it7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:phalcon" /></template>
