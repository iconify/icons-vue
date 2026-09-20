<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fabh_rbkv.css';
import '../../css/l/lk-ht19xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fabh_rbkv"/><path class="lk-ht19xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:search-minus" /></template>
