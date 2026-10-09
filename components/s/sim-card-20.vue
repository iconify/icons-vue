<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa0z9ccux.css';
import '../../css/c/cdardccke.css';
import '../../css/t/tkbzu4bpe.css';
import '../../css/w/wujjhtesw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xa0z9ccux"/><path class="cdardccke"/><path class="tkbzu4bpe"/><path class="wujjhtesw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sim-card-20" /></template>
